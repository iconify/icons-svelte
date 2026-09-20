<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9pcknmql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s9pcknmql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:table-tennis-paddle-and-ball" {...props}></Icon>
