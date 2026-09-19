<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyhj_obng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="gyhj_obng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-arrow-left" {...props}></Icon>
