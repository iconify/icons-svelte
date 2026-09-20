<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsgri6bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsgri6bvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:table" {...props}></Icon>
