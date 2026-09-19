<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuu0zjbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zuu0zjbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wooden-clogs" {...props}></Icon>
