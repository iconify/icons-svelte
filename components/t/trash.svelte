<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqa_y83hy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqa_y83hy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:trash" {...props}></Icon>
