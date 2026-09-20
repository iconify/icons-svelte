<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf8jfjdus.css';
import '../../css/l/ltdti70ft.css';
import '../../css/r/rxr9zbc9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pf8jfjdus"/><path class="ltdti70ft"/><path class="rxr9zbc9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:shopping-shipping-shop" {...props}></Icon>
