<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu19bjyrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hu19bjyrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tron-arrow" {...props}></Icon>
