<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cle0u0bwz.css';
import '../../css/h/hb_oaob_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cle0u0bwz"/><path class="hb_oaob_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:video-24" {...props}></Icon>
