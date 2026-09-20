<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk29hzl3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qk29hzl3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:school" {...props}></Icon>
