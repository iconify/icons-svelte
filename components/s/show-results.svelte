<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iym4j4bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="iym4j4bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:show-results" {...props}></Icon>
