<script setup>
import Table from '../components/Table.vue';
import Row from '../components/Row.vue';

import Col from '../components/Col.vue';
import ColSentence from '../components/ColSentence.vue';
import ColAccent from '../components/ColAccent.vue';
import ColVerb from '../components/ColVerb.vue';

import TextComment from '../components/TextComment.vue';
</script>

<template>
    <TextComment>
		Yesterday since 3 p.m.,
		For some time in the past
    </TextComment>

	<Table>
		<Row>
			<ColSentence>+</ColSentence>
			<ColAccent>*</ColAccent>
			<ColAccent>had <u>been</u></ColAccent>
			<ColVerb>V<sub>ing</sub></ColVerb>
		</Row>
	</Table>

	<Table>
		<Row>
			<ColSentence>-</ColSentence>
			<Col>___</Col>
			<ColAccent>hadn't <u>been</u></ColAccent>
			<ColVerb>V<sub>ing</sub></ColVerb>
		</Row>
	</Table>

	<Table>
		<Row>
			<ColSentence>?</ColSentence>
			<ColAccent>Had</ColAccent>
			<ColAccent>___ <u>been</u></ColAccent>
			<ColVerb>V<sub>ing</sub></ColVerb>
		</Row>
	</Table>
</template>
