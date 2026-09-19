<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkbdgob_u.css';
import '../../css/b/ba4pmswhb.css';
import '../../css/k/kvokd1fvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bkbdgob_u"/><path class="ba4pmswhb"/><path class="kvokd1fvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:speaker3soundwaves" {...props}></Icon>
