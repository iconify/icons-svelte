<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho1-ppbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ho1-ppbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:tag" {...props}></Icon>
