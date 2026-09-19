<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixyy18bln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="ixyy18bln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:tumblr-square" {...props}></Icon>
