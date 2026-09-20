<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3w7q4-ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3w7q4-ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:unarchive-line" {...props}></Icon>
