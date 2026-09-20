<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fry-ov_8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="fry-ov_8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:text-align-justify" {...props}></Icon>
