<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn1a4jxpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tn1a4jxpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:rows-plus" {...props}></Icon>
