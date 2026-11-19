<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imw09osfp.css';
import '../../css/n/n_03jgbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="imw09osfp"/><path class="n_03jgbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:waydroid-dark" {...props}></Icon>
