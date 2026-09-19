<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmuf1bb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path clip-rule="evenodd" class="cmuf1bb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-dribbble" {...props}></Icon>
