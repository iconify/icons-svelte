<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlu2tcchk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="dlu2tcchk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:sort-alpha-down-alt" {...props}></Icon>
