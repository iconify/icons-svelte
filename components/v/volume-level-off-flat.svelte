<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk5l7cbkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kk5l7cbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:volume-level-off-flat" {...props}></Icon>
