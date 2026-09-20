<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjmq40opm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jjmq40opm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:seo-eye-network" {...props}></Icon>
