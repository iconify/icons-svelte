<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov6vt9tgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ov6vt9tgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:usb" {...props}></Icon>
