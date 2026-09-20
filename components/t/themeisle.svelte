<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzik2n9kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yzik2n9kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:themeisle" {...props}></Icon>
