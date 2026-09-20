<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eokmg58xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eokmg58xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:shopping-bag" {...props}></Icon>
