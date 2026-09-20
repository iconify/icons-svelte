<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lasvxn6gs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lasvxn6gs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:view-list" {...props}></Icon>
