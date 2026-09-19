<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8jfljbrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1408};
const content = `<path class="h8jfljbrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:tasks" {...props}></Icon>
