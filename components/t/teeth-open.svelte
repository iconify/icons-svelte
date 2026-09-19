<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce5pb3pjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ce5pb3pjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:teeth-open" {...props}></Icon>
