<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a22_sm6px.css';
import '../../css/y/y3t9q1bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a22_sm6px"/><path class="y3t9q1bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:terminal" {...props}></Icon>
