<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq23lwb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uq23lwb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shield-opposition" {...props}></Icon>
