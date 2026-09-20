<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcsvb_bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcsvb_bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:stars-light" {...props}></Icon>
