<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8tlm64ui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1472};
const content = `<path class="b8tlm64ui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:sleep" {...props}></Icon>
