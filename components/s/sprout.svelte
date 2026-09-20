<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zizw0eb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zizw0eb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:sprout" {...props}></Icon>
