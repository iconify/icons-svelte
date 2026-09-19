<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aje1gjofx.css';
import '../../css/z/z2xdwcchy.css';
import '../../css/o/o-9st-ttp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aje1gjofx"/><path class="z2xdwcchy"/><path class="o-9st-ttp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:server-sharp" {...props}></Icon>
