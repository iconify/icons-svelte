<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvq6pj-fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":680};
const content = `<path class="yvq6pj-fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:tile" {...props}></Icon>
