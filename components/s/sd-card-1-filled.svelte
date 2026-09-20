<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuwblnb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fuwblnb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sd-card-1-filled" {...props}></Icon>
