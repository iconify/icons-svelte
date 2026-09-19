<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z50j0q3zt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="z50j0q3zt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:triangle-solid-left-12" {...props}></Icon>
