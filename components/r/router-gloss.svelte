<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwt69b86a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwt69b86a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:router-gloss" {...props}></Icon>
