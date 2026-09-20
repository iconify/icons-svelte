<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnp6eibir.css';
import '../../css/z/zvjeae8vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xnp6eibir"/><path clip-rule="evenodd" class="zvjeae8vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:ui-panels-none-16" {...props}></Icon>
