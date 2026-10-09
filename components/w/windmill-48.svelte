<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia9w32xvn.css';
import '../../css/h/hoycbqb2w.css';
import '../../css/i/if9dnrb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ia9w32xvn"/><path class="hoycbqb2w"/><path class="if9dnrb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:windmill-48" {...props}></Icon>
