<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnjlp6i1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="lnjlp6i1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:volume-3" {...props}></Icon>
