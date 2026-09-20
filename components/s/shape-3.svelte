<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtcm--bsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtcm--bsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:shape-3" {...props}></Icon>
