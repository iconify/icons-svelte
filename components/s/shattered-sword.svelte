<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmdp---jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qmdp---jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shattered-sword" {...props}></Icon>
