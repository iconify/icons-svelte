<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g51izkbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="g51izkbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:sprout" {...props}></Icon>
