<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umdp1wo1l.css';
import '../../css/x/x1f6fx_5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="umdp1wo1l"/><path class="x1f6fx_5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:weather-rainbow" {...props}></Icon>
