<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck8bl2blq.css';
import '../../css/o/oiuivp-xw.css';
import '../../css/b/brgi00b6i.css';
import '../../css/p/p3d0wwbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck8bl2blq"/><path class="oiuivp-xw"/><path class="brgi00b6i"/><path class="p3d0wwbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:und" {...props}></Icon>
