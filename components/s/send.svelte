<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7qw9qt5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x7qw9qt5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:send" {...props}></Icon>
