<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd4gkhtwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pd4gkhtwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:witch-face" {...props}></Icon>
