<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/o/o00nz9qpp.css';
import '../../css/e/e3y_efb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><path class="o00nz9qpp"/><path class="e3y_efb8k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:user-white-outline" {...props}></Icon>
