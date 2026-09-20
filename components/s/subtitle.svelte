<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sndazvbnj.css';
import '../../css/h/hu6j50bjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sndazvbnj"/><path class="hu6j50bjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:subtitle" {...props}></Icon>
