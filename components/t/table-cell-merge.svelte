<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm9x808by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xm9x808by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:table-cell-merge" {...props}></Icon>
