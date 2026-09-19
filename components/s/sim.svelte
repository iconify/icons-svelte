<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxd28wbfb.css';
import '../../css/j/jpb-onl0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zxd28wbfb"/><path class="jpb-onl0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:sim" {...props}></Icon>
