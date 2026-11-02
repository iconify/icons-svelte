<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgy6df89z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgy6df89z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sunrise-line" {...props}></Icon>
