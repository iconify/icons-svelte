<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq1jstb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fq1jstb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:table-round" {...props}></Icon>
