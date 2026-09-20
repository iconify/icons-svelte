<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xofyrh50b.css';
import '../../css/k/k-n9lzbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xofyrh50b"/><path class="k-n9lzbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:upload" {...props}></Icon>
