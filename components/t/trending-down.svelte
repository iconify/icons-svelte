<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txws23bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txws23bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:trending-down" {...props}></Icon>
