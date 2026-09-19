<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7f9kgmpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b7f9kgmpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:x-diamond-fill" {...props}></Icon>
