<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3jn42bss.css';
import '../../css/s/s5yv7ofdy.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 g3jn42bss"/><rect class="clr-i-outline clr-i-outline-path-2 s5yv7ofdy"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:text-color-line" {...props}></Icon>
