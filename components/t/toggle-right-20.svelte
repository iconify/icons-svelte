<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7u15acll.css';
import '../../css/f/f4uz1jmyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u7u15acll"/><path class="f4uz1jmyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:toggle-right-20" {...props}></Icon>
