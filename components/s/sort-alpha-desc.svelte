<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no9pd3psr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="no9pd3psr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:sort-alpha-desc" {...props}></Icon>
