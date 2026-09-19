<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf5gj7b8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="pf5gj7b8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:ruler-horizontal" {...props}></Icon>
