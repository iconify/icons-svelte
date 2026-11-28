<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-j3qmbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-j3qmbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tea-cup-heart" {...props}></Icon>
