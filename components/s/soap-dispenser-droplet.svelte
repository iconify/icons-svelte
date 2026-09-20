<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv16btbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv16btbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:soap-dispenser-droplet" {...props}></Icon>
