<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwphwybks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jwphwybks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:signal-medium-20" {...props}></Icon>
