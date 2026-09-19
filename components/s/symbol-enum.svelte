<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe8xhe4fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fe8xhe4fr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:symbol-enum" {...props}></Icon>
