<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4krzf3cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z4krzf3cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:sync" {...props}></Icon>
