<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmd-k42xk.css';
import '../../css/g/gbbj8_bmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wmd-k42xk"/><path class="gbbj8_bmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-speaker-48-bold" {...props}></Icon>
