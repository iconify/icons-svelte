<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g52asd2ib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g52asd2ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:stats-bars" {...props}></Icon>
