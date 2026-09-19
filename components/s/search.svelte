<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5505n_tx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1664};
const content = `<path class="m5505n_tx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:search" {...props}></Icon>
