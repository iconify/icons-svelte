<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7e5s8-6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7e5s8-6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:trash-x" {...props}></Icon>
