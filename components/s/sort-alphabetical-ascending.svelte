<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsd6y5yjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="vsd6y5yjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:sort-alphabetical-ascending" {...props}></Icon>
