<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh-b1pbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lh-b1pbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:star-key" {...props}></Icon>
