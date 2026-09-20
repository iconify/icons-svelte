<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz8nilb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pz8nilb-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:star" {...props}></Icon>
