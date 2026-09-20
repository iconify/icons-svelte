<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhoh9byhl.css';
import '../../css/g/gca746gmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jhoh9byhl"/><path class="gca746gmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:tents" {...props}></Icon>
