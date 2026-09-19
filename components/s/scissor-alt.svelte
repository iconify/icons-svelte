<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp0vebcsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sp0vebcsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:scissor-alt" {...props}></Icon>
