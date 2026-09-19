<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvdq9tbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="tvdq9tbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:universal-access" {...props}></Icon>
