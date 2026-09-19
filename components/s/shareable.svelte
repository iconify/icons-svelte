<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko40gccxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ko40gccxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:shareable" {...props}></Icon>
