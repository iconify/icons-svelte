<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzqcv6b8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzqcv6b8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:store-2-line" {...props}></Icon>
