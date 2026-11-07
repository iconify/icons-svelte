<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mms9xzmvs.css';
import '../../css/g/gxzkh2b5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mms9xzmvs"/><path class="gxzkh2b5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sticker-circle-bold-duotone" {...props}></Icon>
