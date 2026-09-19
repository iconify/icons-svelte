<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0n2qbbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n0n2qbbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:swarm" {...props}></Icon>
