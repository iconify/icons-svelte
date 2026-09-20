<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eujag_jpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="eujag_jpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:sort-amount-asc" {...props}></Icon>
