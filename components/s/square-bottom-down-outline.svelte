<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3cwxfump.css';
import '../../css/k/ksuq6mb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3cwxfump"/><path class="ksuq6mb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-bottom-down-outline" {...props}></Icon>
