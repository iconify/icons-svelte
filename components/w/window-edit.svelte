<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa6nr1byd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qa6nr1byd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:window-edit" {...props}></Icon>
