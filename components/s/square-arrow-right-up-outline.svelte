<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m17_tbbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m17_tbbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-arrow-right-up-outline" {...props}></Icon>
