<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujb3xbcfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujb3xbcfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tornado" {...props}></Icon>
