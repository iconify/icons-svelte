<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te1p4dbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="te1p4dbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:thumb-up-duotone" {...props}></Icon>
