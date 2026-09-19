<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er5bmi5ai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="er5bmi5ai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:toothbrush" {...props}></Icon>
