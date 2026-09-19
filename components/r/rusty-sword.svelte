<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0x_k8bnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k0x_k8bnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rusty-sword" {...props}></Icon>
