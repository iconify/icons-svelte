<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxvtyc1ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":609,"height":768};
const content = `<path class="cxvtyc1ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:youtube" {...props}></Icon>
