<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv5fksbba.css';
import '../../css/b/bsakxhhri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rv5fksbba"/><path class="bsakxhhri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vanilla-cookbook" {...props}></Icon>
