<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyypr-b2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="tyypr-b2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:timeline" {...props}></Icon>
