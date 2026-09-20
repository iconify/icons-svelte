<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hym10un3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hym10un3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:style-one-pin-plane-bold" {...props}></Icon>
