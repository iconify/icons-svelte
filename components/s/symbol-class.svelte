<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj6c3qb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zj6c3qb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:symbol-class" {...props}></Icon>
