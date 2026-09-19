<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5dl38bxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="f5dl38bxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:sync-compact" {...props}></Icon>
