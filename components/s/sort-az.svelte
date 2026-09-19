<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn6k9gwzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pn6k9gwzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:sort-az" {...props}></Icon>
