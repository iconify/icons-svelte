<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7p1cf5zq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7p1cf5zq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:scroll" {...props}></Icon>
