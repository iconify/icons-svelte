<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2tro4b9k.css';
import '../../css/i/itttytmxx.css';
import '../../css/x/xmy4_843o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2tro4b9k"/><path class="itttytmxx"/><path class="xmy4_843o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stars-minimalistic-bold" {...props}></Icon>
