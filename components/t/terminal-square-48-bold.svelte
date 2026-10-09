<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrk88uxja.css';
import '../../css/y/y9dqkpbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qrk88uxja"/><path class="y9dqkpbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:terminal-square-48-bold" {...props}></Icon>
