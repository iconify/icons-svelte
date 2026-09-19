<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r08t_8ogy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r08t_8ogy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:volume-1-outline" {...props}></Icon>
