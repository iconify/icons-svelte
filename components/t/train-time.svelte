<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd_kcpkgg.css';
import '../../css/j/j7n6imbex.css';
import '../../css/a/ar36zcbgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wd_kcpkgg"/><path class="j7n6imbex"/><path class="ar36zcbgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:train-time" {...props}></Icon>
