<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx_bzmb5r.css';
import '../../css/w/wg9upwoxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qx_bzmb5r"/><path clip-rule="evenodd" class="wg9upwoxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:shakers-24" {...props}></Icon>
