<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr9w9cuwd.css';
import '../../css/u/umljw05vc.css';
import '../../css/k/k0zklwbhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dr9w9cuwd"/><path class="umljw05vc"/><path class="k0zklwbhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:vault" {...props}></Icon>
