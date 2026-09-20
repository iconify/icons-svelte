<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9cynrzbj.css';
import '../../css/z/zqfr18vyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f9cynrzbj"/><path class="zqfr18vyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:typescript" {...props}></Icon>
