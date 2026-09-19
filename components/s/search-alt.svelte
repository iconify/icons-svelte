<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgof5_bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgof5_bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:search-alt" {...props}></Icon>
