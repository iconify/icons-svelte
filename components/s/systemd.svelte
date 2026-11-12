<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqod05bbx.css';
import '../../css/l/lo6iqdbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qqod05bbx"/><path class="lo6iqdbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:systemd" {...props}></Icon>
