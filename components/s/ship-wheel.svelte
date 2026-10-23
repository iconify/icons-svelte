<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrn6fsfft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrn6fsfft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:ship-wheel" {...props}></Icon>
