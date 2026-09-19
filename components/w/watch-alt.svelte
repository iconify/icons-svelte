<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n23vf1bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n23vf1bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:watch-alt" {...props}></Icon>
