<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-j9djbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-j9djbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-chevron-up-filled" {...props}></Icon>
