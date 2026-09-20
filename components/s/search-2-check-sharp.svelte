<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5urce02d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5urce02d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:search-2-check-sharp" {...props}></Icon>
