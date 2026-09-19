<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7_hf7wcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r7_hf7wcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:train-freight-front-fill" {...props}></Icon>
