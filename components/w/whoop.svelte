<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddx_2psae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":39,"height":39};
const content = `<path class="ddx_2psae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:whoop" {...props}></Icon>
