<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2l1x3bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b2l1x3bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:street-cabinet-drop" {...props}></Icon>
