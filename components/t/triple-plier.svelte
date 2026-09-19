<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_pyil1ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p_pyil1ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:triple-plier" {...props}></Icon>
