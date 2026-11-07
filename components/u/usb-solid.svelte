<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h15mlj49b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h15mlj49b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:usb-solid" {...props}></Icon>
