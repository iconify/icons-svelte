<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s759206rp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="s759206rp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:tty" {...props}></Icon>
