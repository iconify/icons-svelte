<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-_nxdr2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-_nxdr2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:toggles-sharp" {...props}></Icon>
