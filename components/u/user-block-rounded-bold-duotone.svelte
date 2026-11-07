<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzeuvdbtu.css';
import '../../css/l/lc21qzuqt.css';
import '../../css/b/ba30w5b_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hzeuvdbtu"/><path class="lc21qzuqt"/><path class="ba30w5b_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-block-rounded-bold-duotone" {...props}></Icon>
