<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta7hfpbbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ta7hfpbbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:train-front" {...props}></Icon>
