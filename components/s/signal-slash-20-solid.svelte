<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6e4u0b6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b6e4u0b6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:signal-slash-20-solid" {...props}></Icon>
