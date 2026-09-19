<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g27f8y-km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="g27f8y-km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:square-nfi" {...props}></Icon>
