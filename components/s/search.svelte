<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akpogxbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="akpogxbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:search" {...props}></Icon>
