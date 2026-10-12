<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmx_sxbxs.css';
import '../../css/c/c582bi82c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kmx_sxbxs"/><path class="c582bi82c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:test-tube-fill-20" {...props}></Icon>
