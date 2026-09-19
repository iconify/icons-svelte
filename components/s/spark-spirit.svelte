<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6bplybgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p6bplybgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spark-spirit" {...props}></Icon>
