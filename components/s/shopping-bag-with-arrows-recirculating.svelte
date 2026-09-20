<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfhcms4tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sfhcms4tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-arrows-recirculating" {...props}></Icon>
