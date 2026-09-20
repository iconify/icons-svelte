<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3b55n-_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d3b55n-_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ruler" {...props}></Icon>
