<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpxw-t44r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rpxw-t44r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:sort-up" {...props}></Icon>
