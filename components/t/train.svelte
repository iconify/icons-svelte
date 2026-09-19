<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzlyre6gz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":579,"height":1024};
const content = `<path class="bzlyre6gz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:train" {...props}></Icon>
