<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3r41qfxn.css';
import '../../css/s/str-f1rew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="t3r41qfxn"/><path class="str-f1rew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:zoom-out" {...props}></Icon>
