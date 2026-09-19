<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy2faccfl.css';
import '../../css/u/u7k7a9bky.css';
import '../../css/d/d12rxmbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="qy2faccfl"/><circle class="u7k7a9bky"/><path class="d12rxmbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:shopping-cart" {...props}></Icon>
