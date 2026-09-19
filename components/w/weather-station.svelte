<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf38nmbzc.css';
import '../../css/j/j_fgb0h4o.css';
import '../../css/e/e-_ammf2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tf38nmbzc"/><path class="j_fgb0h4o"/><path class="e-_ammf2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:weather-station" {...props}></Icon>
