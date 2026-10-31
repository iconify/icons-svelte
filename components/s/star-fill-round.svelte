<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx9z-d2ap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx9z-d2ap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:star-fill-round" {...props}></Icon>
