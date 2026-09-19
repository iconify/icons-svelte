<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqfm60b_p.css';
import '../../css/h/hrtye35bf.css';
import '../../css/g/gskti7b-z.css';
import '../../css/z/zpaj0ybty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qqfm60b_p"/><path class="hrtye35bf"/><path class="gskti7b-z"/><circle class="zpaj0ybty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:sixpointedstarwithdot" {...props}></Icon>
