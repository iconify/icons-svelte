<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdwl-gbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="gdwl-gbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:table-cells-column-lock" {...props}></Icon>
