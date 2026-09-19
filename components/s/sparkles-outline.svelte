<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hitn88byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hitn88byj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:sparkles-outline" {...props}></Icon>
