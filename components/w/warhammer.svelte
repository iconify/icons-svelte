<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie2v73wnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ie2v73wnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:warhammer" {...props}></Icon>
