<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_v1zhbtb.css';
import '../../css/d/d5acjcb7w.css';
import '../../css/u/u2kjx6byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a_v1zhbtb"/><path class="d5acjcb7w"/><path class="u2kjx6byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:woman-in-manual-wheelchair-facing-right" {...props}></Icon>
