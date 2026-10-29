<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-018mx1x.css';
import '../../css/x/xoollor0t.css';
import '../../css/d/dn5423bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-018mx1x wm-k"/><path class="wm-k xoollor0t"/><path class="dn5423bcn wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:sticky-note" {...props}></Icon>
