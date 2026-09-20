<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlf1ngy_p.css';
import '../../css/m/mw_oixbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlf1ngy_p"/><path clip-rule="evenodd" class="mw_oixbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:shop-duotone" {...props}></Icon>
