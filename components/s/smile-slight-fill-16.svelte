<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3fi1ehfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f3fi1ehfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:smile-slight-fill-16" {...props}></Icon>
