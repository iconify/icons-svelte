<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atcz-gbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="atcz-gbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:vue" {...props}></Icon>
