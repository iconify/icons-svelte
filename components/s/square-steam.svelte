<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1c1qub4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="h1c1qub4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:square-steam" {...props}></Icon>
