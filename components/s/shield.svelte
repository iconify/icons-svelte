<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq9tt3b9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="yq9tt3b9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:shield" {...props}></Icon>
