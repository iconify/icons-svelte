<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-opjvbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-opjvbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:tracking-outline" {...props}></Icon>
