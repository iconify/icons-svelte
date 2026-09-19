<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6zcjhb8g.css';
import '../../css/v/vt3ssfbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j6zcjhb8g"/><path class="vt3ssfbtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rule-data-quality" {...props}></Icon>
