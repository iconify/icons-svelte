<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4cwfwboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4cwfwboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-chevrons-up-filled" {...props}></Icon>
