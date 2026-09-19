<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o76egzb2i.css';
import '../../css/p/pu-6-0j8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o76egzb2i"/><path class="pu-6-0j8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:square-chev-down" {...props}></Icon>
