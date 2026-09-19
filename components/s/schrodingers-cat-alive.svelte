<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqj0bns5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kqj0bns5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:schrodingers-cat-alive" {...props}></Icon>
