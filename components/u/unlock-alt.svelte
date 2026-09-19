<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vusf_hb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vusf_hb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:unlock-alt" {...props}></Icon>
