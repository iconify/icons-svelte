<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih_hx3b5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ih_hx3b5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:scanner-1-remix" {...props}></Icon>
