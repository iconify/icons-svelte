<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou0e18q7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ou0e18q7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-chevron-down-round" {...props}></Icon>
