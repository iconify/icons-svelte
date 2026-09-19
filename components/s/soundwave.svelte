<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlc6okb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wlc6okb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:soundwave" {...props}></Icon>
