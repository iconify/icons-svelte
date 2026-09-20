<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us2wi3bkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="us2wi3bkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-arrow-right-bold" {...props}></Icon>
