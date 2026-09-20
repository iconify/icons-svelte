<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znzk-c_8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":214};
const content = `<path class="znzk-c_8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:stripe" {...props}></Icon>
