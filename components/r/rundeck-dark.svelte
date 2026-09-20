<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0gh8ac0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c0gh8ac0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rundeck-dark" {...props}></Icon>
