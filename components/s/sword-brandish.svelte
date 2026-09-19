<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/naovz_vyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="naovz_vyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sword-brandish" {...props}></Icon>
