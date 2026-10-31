<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd3j_obfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yd3j_obfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:umbrella-fill-round" {...props}></Icon>
