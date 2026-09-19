<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvrdeibos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pvrdeibos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:stop-circle-sharp" {...props}></Icon>
