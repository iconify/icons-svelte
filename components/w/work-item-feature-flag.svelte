<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xovstybjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xovstybjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:work-item-feature-flag" {...props}></Icon>
