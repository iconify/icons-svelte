<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5d9s8bzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j5d9s8bzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:work-item-new" {...props}></Icon>
