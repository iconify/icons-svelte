<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n91md1mwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n91md1mwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:zoom-in" {...props}></Icon>
