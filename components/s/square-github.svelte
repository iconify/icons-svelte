<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xye8dcczv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="xye8dcczv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:square-github" {...props}></Icon>
