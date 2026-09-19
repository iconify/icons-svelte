<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq7t5p63g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sq7t5p63g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:scarf" {...props}></Icon>
