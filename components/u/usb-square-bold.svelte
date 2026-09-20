<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzw00zbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dzw00zbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:usb-square-bold" {...props}></Icon>
