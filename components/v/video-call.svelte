<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx5ltho2y.css';
import '../../css/x/xoymbvb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kx5ltho2y"/><path class="xoymbvb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:video-call" {...props}></Icon>
