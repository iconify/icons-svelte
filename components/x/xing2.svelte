<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9robzzqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t9robzzqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:xing2" {...props}></Icon>
