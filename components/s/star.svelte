<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h50m28b6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h50m28b6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:star" {...props}></Icon>
