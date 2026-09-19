<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hde9zom3i.css';
import '../../css/d/di_8scctl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hde9zom3i"/><path class="di_8scctl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:text-size" {...props}></Icon>
