<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz4b3lhfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lz4b3lhfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-color-fill" {...props}></Icon>
