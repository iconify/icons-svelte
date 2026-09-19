<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftqefabbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":490,"height":512};
const content = `<path class="ftqefabbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:truffle" {...props}></Icon>
