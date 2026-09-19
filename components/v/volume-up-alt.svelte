<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sokxb_p0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sokxb_p0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:volume-up-alt" {...props}></Icon>
