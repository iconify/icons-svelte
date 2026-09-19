<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jed9xlkuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jed9xlkuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:sloth" {...props}></Icon>
