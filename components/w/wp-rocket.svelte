<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ili7pu_wf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ili7pu_wf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wp-rocket" {...props}></Icon>
