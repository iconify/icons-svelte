<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_f83bmeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="q_f83bmeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:square" {...props}></Icon>
