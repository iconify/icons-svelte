<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj6o8abyb.css';
import '../../css/b/bnus8tbil.css';
import '../../css/t/t3kxshl8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":262,"height":262,"left":-3};
const content = `<path class="lj6o8abyb"/><path class="bnus8tbil"/><path class="t3kxshl8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sourcegraph" {...props}></Icon>
