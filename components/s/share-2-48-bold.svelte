<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um4cf3bps.css';
import '../../css/g/g2l6abblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="um4cf3bps"/><path class="g2l6abblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:share-2-48-bold" {...props}></Icon>
