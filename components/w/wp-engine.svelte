<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt76y9bvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt76y9bvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wp-engine" {...props}></Icon>
