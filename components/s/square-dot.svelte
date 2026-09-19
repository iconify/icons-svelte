<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0-fa_nrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w0-fa_nrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:square-dot" {...props}></Icon>
