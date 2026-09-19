<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td2ntbexb.css';
import '../../css/w/w74p6ub3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="td2ntbexb"/><path class="w74p6ub3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:vertx" {...props}></Icon>
