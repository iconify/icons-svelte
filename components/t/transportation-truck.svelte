<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9xke1qvt.css';
import '../../css/u/u71vq3b-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u9xke1qvt"/><path class="u71vq3b-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:transportation-truck" {...props}></Icon>
