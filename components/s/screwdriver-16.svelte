<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veidlab1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="veidlab1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:screwdriver-16" {...props}></Icon>
