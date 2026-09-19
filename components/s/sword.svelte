<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m89ht4ona.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m89ht4ona"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:sword" {...props}></Icon>
