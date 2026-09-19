<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esj_debvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="esj_debvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:videocam-off-sharp" {...props}></Icon>
