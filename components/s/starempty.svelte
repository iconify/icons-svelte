<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1nfcimdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":778,"height":739};
const content = `<path class="d1nfcimdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:starempty" {...props}></Icon>
