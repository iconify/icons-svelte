<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo9s7db4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="eo9s7db4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:table-first-column" {...props}></Icon>
