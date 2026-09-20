<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrtf_jb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrtf_jb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:wifi-sync" {...props}></Icon>
