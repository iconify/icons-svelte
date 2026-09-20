<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ema3nk49z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ema3nk49z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:scanning" {...props}></Icon>
