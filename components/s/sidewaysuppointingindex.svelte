<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp7_e5biu.css';
import '../../css/f/foa_mcc1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dp7_e5biu"/><path class="foa_mcc1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:sidewaysuppointingindex" {...props}></Icon>
