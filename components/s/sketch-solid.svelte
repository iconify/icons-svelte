<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wztfgntmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wztfgntmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:sketch-solid" {...props}></Icon>
