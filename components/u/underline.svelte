<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs8trmb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hs8trmb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:underline" {...props}></Icon>
