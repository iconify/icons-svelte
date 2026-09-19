<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecuu_-sxs.css';
import '../../css/j/j6ag-3bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecuu_-sxs"/><path class="j6ag-3bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:warning-outline" {...props}></Icon>
