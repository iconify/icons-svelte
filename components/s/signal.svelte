<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7c-rze5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y7c-rze5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:signal" {...props}></Icon>
