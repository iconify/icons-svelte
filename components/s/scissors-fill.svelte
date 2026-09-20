<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfjvhv-9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfjvhv-9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:scissors-fill" {...props}></Icon>
