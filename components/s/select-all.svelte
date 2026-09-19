<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcueq7bxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="tcueq7bxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:select-all" {...props}></Icon>
