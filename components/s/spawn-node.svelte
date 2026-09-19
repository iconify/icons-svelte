<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql7d5ob1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ql7d5ob1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spawn-node" {...props}></Icon>
