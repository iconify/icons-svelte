<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw5lexb-j.css';
import '../../css/y/y4rdwmmfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gw5lexb-j"/><path class="y4rdwmmfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:shopping-basket" {...props}></Icon>
