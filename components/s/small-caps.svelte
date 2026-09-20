<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si9wz7b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="si9wz7b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:small-caps" {...props}></Icon>
