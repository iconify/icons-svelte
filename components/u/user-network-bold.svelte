<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3al76g9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3al76g9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:user-network-bold" {...props}></Icon>
