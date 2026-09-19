<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jajrpoe9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jajrpoe9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:text-tracking" {...props}></Icon>
