<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq-8jxbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oq-8jxbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:visa-dark" {...props}></Icon>
