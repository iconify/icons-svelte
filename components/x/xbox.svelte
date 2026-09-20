<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz-gusbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":88,"height":88};
const content = `<path class="dz-gusbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:xbox" {...props}></Icon>
