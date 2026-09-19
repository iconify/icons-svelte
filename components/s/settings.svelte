<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aud9bzb6h.css';
import '../../css/x/x4saxe2xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aud9bzb6h"/><path class="x4saxe2xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:settings" {...props}></Icon>
