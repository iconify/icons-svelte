<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx6tlvbkb.css';
import '../../css/u/uk9yq28xx.css';
import '../../css/d/d3ye85bme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="tx6tlvbkb"><path class="uk9yq28xx"/><path class="d3ye85bme"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:socketio" {...props}></Icon>
