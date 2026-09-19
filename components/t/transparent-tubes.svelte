<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3npp-y-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o3npp-y-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:transparent-tubes" {...props}></Icon>
