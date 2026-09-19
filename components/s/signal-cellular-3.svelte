<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avrykfb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="avrykfb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:signal-cellular-3" {...props}></Icon>
