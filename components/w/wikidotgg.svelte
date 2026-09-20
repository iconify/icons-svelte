<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3_iv84nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3_iv84nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wikidotgg" {...props}></Icon>
