<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc_x2tbuz.css';
import '../../css/m/mms9xzmvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mc_x2tbuz"/><path class="mms9xzmvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sticker-circle-bold" {...props}></Icon>
