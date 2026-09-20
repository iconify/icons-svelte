<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_luvib9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="t_luvib9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:theatre-11" {...props}></Icon>
