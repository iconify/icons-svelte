<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkejixr2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkejixr2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:stairs-arrow-up-right" {...props}></Icon>
