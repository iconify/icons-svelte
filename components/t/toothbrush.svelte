<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asxgz14_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="asxgz14_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:toothbrush" {...props}></Icon>
