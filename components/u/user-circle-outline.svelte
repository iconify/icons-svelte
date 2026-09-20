<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv40kvbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yv40kvbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:user-circle-outline" {...props}></Icon>
