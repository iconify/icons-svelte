<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thlt711ob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="thlt711ob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:tux" {...props}></Icon>
