<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bri9ce21d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bri9ce21d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:taiwan-dollar" {...props}></Icon>
