<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf-49vp4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="tf-49vp4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:upload-stroke-12" {...props}></Icon>
