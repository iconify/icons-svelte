<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohd3jjbmj.css';
import '../../css/h/hhno8jbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ohd3jjbmj"/><circle class="hhno8jbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:user-active" {...props}></Icon>
