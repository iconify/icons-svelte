<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c98j8rb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c98j8rb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:symbol-enum-member" {...props}></Icon>
