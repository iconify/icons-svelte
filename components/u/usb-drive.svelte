<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm9ue06lw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="vm9ue06lw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:usb-drive" {...props}></Icon>
