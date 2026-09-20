<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyc_qkbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyc_qkbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:spotify-fill" {...props}></Icon>
