<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti3pf4j_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti3pf4j_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:slider-01" {...props}></Icon>
