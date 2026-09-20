<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh3143b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zh3143b3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:scan-text-sharp-fill" {...props}></Icon>
