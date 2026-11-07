<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuo7dyblv.css';
import '../../css/l/lc21qzuqt.css';
import '../../css/v/v-gsn_r9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yuo7dyblv"/><path class="lc21qzuqt"/><path class="v-gsn_r9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-cross-bold-duotone" {...props}></Icon>
