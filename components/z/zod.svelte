<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2p_gdcsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2p_gdcsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:zod" {...props}></Icon>
