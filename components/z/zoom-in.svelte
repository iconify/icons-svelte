<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_8q9z4vg.css';
import '../../css/o/oof_74yzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="x_8q9z4vg"/><path class="oof_74yzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:zoom-in" {...props}></Icon>
