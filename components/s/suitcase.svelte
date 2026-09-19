<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugjzi838y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ugjzi838y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:suitcase" {...props}></Icon>
