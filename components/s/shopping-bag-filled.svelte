<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5i1vx9wz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e5i1vx9wz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:shopping-bag-filled" {...props}></Icon>
