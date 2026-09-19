<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqzvm0boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yqzvm0boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:smartphone" {...props}></Icon>
