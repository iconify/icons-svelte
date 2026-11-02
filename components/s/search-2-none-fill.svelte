<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_8zmdxsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_8zmdxsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:search-2-none-fill" {...props}></Icon>
