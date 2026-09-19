<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfk20ob_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lfk20ob_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:seedling" {...props}></Icon>
