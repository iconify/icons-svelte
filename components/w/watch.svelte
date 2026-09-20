<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8jixq.css';
import '../../css/q/qq3t6k.css';
import '../../css/d/d-45nhxp.css';
import '../../css/r/r-from-0px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8jixq"/><circle class="qq3t6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:watch" {...props}></Icon>
