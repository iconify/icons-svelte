<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnln94bkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnln94bkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:text-underline" {...props}></Icon>
