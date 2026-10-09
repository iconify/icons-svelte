<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d17mx3bfs.css';
import '../../css/z/zr5giubst.css';
import '../../css/z/z01z8_btg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d17mx3bfs"/><path class="zr5giubst"/><path class="z01z8_btg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:type-20" {...props}></Icon>
