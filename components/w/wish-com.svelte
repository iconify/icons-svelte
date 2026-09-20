<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyf7383ma.css';
import '../../css/o/o703l3o2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nyf7383ma"/><path class="o703l3o2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wish-com" {...props}></Icon>
