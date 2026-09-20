<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_xl4hb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_xl4hb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:search-normal-filled" {...props}></Icon>
