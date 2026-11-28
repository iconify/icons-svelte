<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usvxjnb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usvxjnb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:usb-check" {...props}></Icon>
