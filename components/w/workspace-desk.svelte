<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3y37rbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3y37rbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:workspace-desk" {...props}></Icon>
