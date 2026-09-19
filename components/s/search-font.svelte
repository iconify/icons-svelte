<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz9ykdvoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uz9ykdvoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:search-font" {...props}></Icon>
