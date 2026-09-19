<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pta22w69a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pta22w69a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:tag" {...props}></Icon>
