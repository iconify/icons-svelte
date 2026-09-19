<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u75xkq--u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="u75xkq--u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:status-circle-question-mark" {...props}></Icon>
