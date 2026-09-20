<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg95s5baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bg95s5baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:signature" {...props}></Icon>
