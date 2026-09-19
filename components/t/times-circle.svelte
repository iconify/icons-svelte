<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9ax1cc5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="m9ax1cc5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:times-circle" {...props}></Icon>
