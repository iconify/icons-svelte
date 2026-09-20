<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fabh_rbkv.css';
import '../../css/g/gh1c2r79w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fabh_rbkv"/><path class="gh1c2r79w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:search-plus" {...props}></Icon>
