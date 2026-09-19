<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tak0hzc8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tak0hzc8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:view-module" {...props}></Icon>
