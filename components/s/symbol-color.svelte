<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_40l7-5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l_40l7-5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:symbol-color" {...props}></Icon>
