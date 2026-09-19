<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbb_oabdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbb_oabdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:rows-two" {...props}></Icon>
