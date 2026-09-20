<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgiie_btq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tgiie_btq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:wheel-barrow" {...props}></Icon>
