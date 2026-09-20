<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcivn0byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcivn0byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ruler-measure" {...props}></Icon>
