<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfa8sx9at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pfa8sx9at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:sphere-shape-remix" {...props}></Icon>
