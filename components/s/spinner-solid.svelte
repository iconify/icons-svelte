<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7u7tdb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="t7u7tdb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:spinner-solid" {...props}></Icon>
