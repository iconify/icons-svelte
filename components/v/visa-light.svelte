<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-9bxbbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z-9bxbbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:visa-light" {...props}></Icon>
