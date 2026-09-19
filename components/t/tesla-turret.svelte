<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azk1c0b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="azk1c0b3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tesla-turret" {...props}></Icon>
