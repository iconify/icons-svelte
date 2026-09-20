<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhtl3hy3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="yhtl3hy3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:text-telephone" {...props}></Icon>
