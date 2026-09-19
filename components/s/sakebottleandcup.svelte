<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmeesubxi.css';
import '../../css/l/l08ji0b1b.css';
import '../../css/q/q8whoub3o.css';
import '../../css/b/bi6rp_ibq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rmeesubxi"/><path class="l08ji0b1b"/><path class="q8whoub3o"/><path class="bi6rp_ibq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:sakebottleandcup" {...props}></Icon>
