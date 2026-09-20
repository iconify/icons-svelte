<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kji6v2qse.css';
import '../../css/z/ztfq1ibst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kji6v2qse"/><path class="ztfq1ibst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:screen-mirroring-filled" {...props}></Icon>
