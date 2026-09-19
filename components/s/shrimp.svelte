<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s82z5ebmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s82z5ebmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shrimp" {...props}></Icon>
