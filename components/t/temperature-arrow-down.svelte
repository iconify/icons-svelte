<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1edp2nss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="q1edp2nss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:temperature-arrow-down" {...props}></Icon>
