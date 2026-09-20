<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apgp81bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apgp81bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:upload-sharp" {...props}></Icon>
