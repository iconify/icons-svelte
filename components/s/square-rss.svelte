<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghr2c-kae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ghr2c-kae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:square-rss" {...props}></Icon>
