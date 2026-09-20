<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u21fx_xji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u21fx_xji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:tide" {...props}></Icon>
