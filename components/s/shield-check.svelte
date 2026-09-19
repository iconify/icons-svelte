<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jngw48yvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2016,"height":2176};
const content = `<path class="jngw48yvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:shield-check" {...props}></Icon>
