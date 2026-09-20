<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejccd-dpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ejccd-dpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:scanner" {...props}></Icon>
