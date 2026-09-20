<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b274l8q4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="b274l8q4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:toolbox" {...props}></Icon>
