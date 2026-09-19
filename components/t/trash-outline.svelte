<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gowarsb4c.css';
import '../../css/b/b0c14i84a.css';
import '../../css/f/fyztchb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gowarsb4c"/><path class="b0c14i84a"/><path class="fyztchb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:trash-outline" {...props}></Icon>
