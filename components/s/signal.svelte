<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7_-a7ixx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7_-a7ixx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:signal" {...props}></Icon>
