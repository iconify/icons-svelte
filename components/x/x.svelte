<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsekoabps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":537,"height":654};
const content = `<path class="xsekoabps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:x" {...props}></Icon>
