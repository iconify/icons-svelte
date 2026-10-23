<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvhvuxb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvhvuxb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:star-minus" {...props}></Icon>
