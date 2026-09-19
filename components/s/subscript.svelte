<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehsl2h5wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ehsl2h5wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:subscript" {...props}></Icon>
