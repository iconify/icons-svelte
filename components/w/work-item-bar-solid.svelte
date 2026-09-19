<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0kmr-bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="c0kmr-bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:work-item-bar-solid" {...props}></Icon>
