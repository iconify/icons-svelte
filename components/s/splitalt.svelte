<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8ft-ub9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":1025};
const content = `<path class="c8ft-ub9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:splitalt" {...props}></Icon>
