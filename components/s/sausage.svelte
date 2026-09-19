<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mspky1buw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mspky1buw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sausage" {...props}></Icon>
