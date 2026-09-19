<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/himehxbog.css';
import '../../css/j/jhsk6hp0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="himehxbog"/><path class="jhsk6hp0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:volume-full" {...props}></Icon>
