<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpi6zpbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gpi6zpbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sailboat" {...props}></Icon>
