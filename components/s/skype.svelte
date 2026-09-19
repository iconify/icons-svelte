<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycxm-968i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="ycxm-968i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:skype" {...props}></Icon>
