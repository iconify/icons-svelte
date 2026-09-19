<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h20--1bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h20--1bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:sms" {...props}></Icon>
