<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnafdbble.css';
import '../../css/i/in6vio3jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nnafdbble"/><path class="in6vio3jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:train-20" {...props}></Icon>
