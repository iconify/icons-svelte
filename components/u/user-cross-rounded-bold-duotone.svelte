<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuo7dyblv.css';
import '../../css/l/lc21qzuqt.css';
import '../../css/u/uhr9dibke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yuo7dyblv"/><path class="lc21qzuqt"/><path class="uhr9dibke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-cross-rounded-bold-duotone" {...props}></Icon>
