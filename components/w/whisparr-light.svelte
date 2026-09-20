<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjt81ppiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zjt81ppiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:whisparr-light" {...props}></Icon>
