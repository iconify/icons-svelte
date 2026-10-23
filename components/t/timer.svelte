<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/m/mr0ya4bou.css';
import '../../css/g/g4_6w77hr.css';
import '../../css/n/n8ny8e3ug.css';
import '../../css/t/tyi8o0bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="mr0ya4bou"/><path class="g4_6w77hr"/><path class="n8ny8e3ug"/><path class="tyi8o0bkh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:timer" {...props}></Icon>
