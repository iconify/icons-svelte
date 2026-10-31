<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0li63b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0li63b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:square-letter-x" {...props}></Icon>
