<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl0y2rbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gl0y2rbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:text-indent-left" {...props}></Icon>
