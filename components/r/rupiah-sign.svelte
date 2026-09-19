<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr19c78yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="hr19c78yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:rupiah-sign" {...props}></Icon>
