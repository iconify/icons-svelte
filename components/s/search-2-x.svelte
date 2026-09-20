<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqox9xelv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqox9xelv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:search-2-x" {...props}></Icon>
