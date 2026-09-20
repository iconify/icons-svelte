<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2v34pbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="g2v34pbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:volume-control" {...props}></Icon>
