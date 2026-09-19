<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqyxfs48f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hqyxfs48f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:upload2" {...props}></Icon>
