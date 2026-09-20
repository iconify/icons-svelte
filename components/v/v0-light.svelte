<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0s4wmb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d0s4wmb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:v0-light" {...props}></Icon>
