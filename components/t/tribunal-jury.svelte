<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nby1hwv0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nby1hwv0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tribunal-jury" {...props}></Icon>
