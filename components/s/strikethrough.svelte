<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guldh2qfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="guldh2qfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:strikethrough" {...props}></Icon>
