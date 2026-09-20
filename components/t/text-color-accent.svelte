<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjbno271j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjbno271j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:text-color-accent" {...props}></Icon>
