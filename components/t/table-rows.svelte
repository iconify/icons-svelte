<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcz__fbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcz__fbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:table-rows" {...props}></Icon>
