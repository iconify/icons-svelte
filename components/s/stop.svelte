<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb4h_tb7x.css';
import '../../css/e/eozwp4bxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fb4h_tb7x"/><path class="eozwp4bxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:stop" {...props}></Icon>
