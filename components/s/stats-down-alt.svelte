<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0ci-rg2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0ci-rg2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:stats-down-alt" {...props}></Icon>
