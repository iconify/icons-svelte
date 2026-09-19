<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4v87jbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="q4v87jbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:undo" {...props}></Icon>
