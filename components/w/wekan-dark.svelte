<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw3mel2bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uw3mel2bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wekan-dark" {...props}></Icon>
