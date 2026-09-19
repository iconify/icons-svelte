<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-2li_llf.css';
import '../../css/n/n9o42e7zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j-2li_llf"/><path class="n9o42e7zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:sort-amount-asc" {...props}></Icon>
