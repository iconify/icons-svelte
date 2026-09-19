<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yigh9tbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="yigh9tbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:superman" {...props}></Icon>
