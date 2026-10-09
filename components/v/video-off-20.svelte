<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1rxfewyg.css';
import '../../css/f/fx_ekx88i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x1rxfewyg"/><path class="fx_ekx88i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:video-off-20" {...props}></Icon>
