<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehi1ijv8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehi1ijv8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:stitches-outline-24px" {...props}></Icon>
