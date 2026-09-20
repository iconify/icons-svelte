<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt4i1t6ih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lt4i1t6ih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:thermometer" {...props}></Icon>
