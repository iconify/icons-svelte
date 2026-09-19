<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-v5zg_-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-v5zg_-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:square-stack" {...props}></Icon>
