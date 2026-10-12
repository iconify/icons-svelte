<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uye2wsfpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uye2wsfpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-off-filled" {...props}></Icon>
