<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8piecpte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y8piecpte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:spinner4" {...props}></Icon>
