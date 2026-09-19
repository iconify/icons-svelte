<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu0pjkb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gu0pjkb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:screen-time" {...props}></Icon>
