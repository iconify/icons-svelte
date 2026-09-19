<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1yh6f2dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":766};
const content = `<path class="u1yh6f2dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:search" {...props}></Icon>
