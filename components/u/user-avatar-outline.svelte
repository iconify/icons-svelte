<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsbfe76of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lsbfe76of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:user-avatar-outline" {...props}></Icon>
