<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzw7q5bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xzw7q5bew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:tty" {...props}></Icon>
