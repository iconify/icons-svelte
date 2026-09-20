<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz9yxmbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tz9yxmbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:search-minus" {...props}></Icon>
