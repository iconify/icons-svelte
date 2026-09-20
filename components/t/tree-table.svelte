<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbwtn-biq.css';
import '../../css/e/e7ttr_boe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gbwtn-biq"/><path class="e7ttr_boe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:tree-table" {...props}></Icon>
