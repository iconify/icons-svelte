<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1-dhmbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1-dhmbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:tools-kitchen-2" {...props}></Icon>
