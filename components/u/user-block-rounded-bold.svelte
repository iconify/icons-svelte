<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzeuvdbtu.css';
import '../../css/v/vdoxwhb2d.css';
import '../../css/l/lc21qzuqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hzeuvdbtu"/><path class="vdoxwhb2d"/><path class="lc21qzuqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-block-rounded-bold" {...props}></Icon>
