<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3qa7t8dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3qa7t8dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:shopping-bag" {...props}></Icon>
