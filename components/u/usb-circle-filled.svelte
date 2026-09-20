<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdv9229rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kdv9229rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:usb-circle-filled" {...props}></Icon>
