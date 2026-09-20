<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrmsgxw5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hrmsgxw5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:schneider-electric-dark" {...props}></Icon>
