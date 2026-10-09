<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4bzr0bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p4bzr0bap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-20-bold" {...props}></Icon>
