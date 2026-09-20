<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1p0mx41p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v1p0mx41p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:work-item-enhancement" {...props}></Icon>
