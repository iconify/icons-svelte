<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/niza58bhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="niza58bhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:trapezoid" {...props}></Icon>
