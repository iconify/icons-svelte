<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do_oleb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="do_oleb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:square-fill-16" {...props}></Icon>
