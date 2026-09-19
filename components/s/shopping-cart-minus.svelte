<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy2faccfl.css';
import '../../css/u/u7k7a9bky.css';
import '../../css/t/t2ne504af.css';
import '../../css/z/zvtwl4sqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="qy2faccfl"/><circle class="u7k7a9bky"/><path class="t2ne504af"/><path class="zvtwl4sqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:shopping-cart-minus" {...props}></Icon>
