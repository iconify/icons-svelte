<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1j9atx_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="b1j9atx_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:waste-basket-10" {...props}></Icon>
