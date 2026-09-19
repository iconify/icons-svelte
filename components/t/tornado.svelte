<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgi5fe4yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pgi5fe4yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:tornado" {...props}></Icon>
