<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f68_n4bcj.css';
import '../../css/m/mp7nbmbcx.css';
import '../../css/m/m17qjo6op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f68_n4bcj"/><path class="mp7nbmbcx"/><path class="m17qjo6op"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:system-interface" {...props}></Icon>
