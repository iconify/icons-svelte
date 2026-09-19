<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9n-v7-5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x9n-v7-5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:strongbox" {...props}></Icon>
