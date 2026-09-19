<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uorm58bmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uorm58bmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:strawberry" {...props}></Icon>
