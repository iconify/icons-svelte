<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0t_852bq.css';
import '../../css/l/lihbolbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0t_852bq"/><circle class="lihbolbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:shopping-tag" {...props}></Icon>
