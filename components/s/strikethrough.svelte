<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmoz2bcoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lmoz2bcoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:strikethrough" {...props}></Icon>
