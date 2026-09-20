<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fabh_rbkv.css';
import '../../css/l/lk-ht19xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fabh_rbkv"/><path class="lk-ht19xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:search-minus" {...props}></Icon>
