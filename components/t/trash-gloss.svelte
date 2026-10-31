<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utd5y4bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utd5y4bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:trash-gloss" {...props}></Icon>
