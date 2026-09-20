<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b99mwcchm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b99mwcchm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:table-merge-cells" {...props}></Icon>
