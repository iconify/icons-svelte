<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg5qm8m1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg5qm8m1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:sword" {...props}></Icon>
