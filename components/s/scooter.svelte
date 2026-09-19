<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbm9v9sot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mbm9v9sot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:scooter" {...props}></Icon>
