<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3z_u7bad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g3z_u7bad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:user-follow" {...props}></Icon>
