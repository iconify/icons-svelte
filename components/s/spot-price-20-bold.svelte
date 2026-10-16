<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdwp1kh1x.css';
import '../../css/b/b3qkz99-a.css';
import '../../css/d/d1xy-t7vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xdwp1kh1x"/><path class="b3qkz99-a"/><path class="d1xy-t7vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spot-price-20-bold" {...props}></Icon>
