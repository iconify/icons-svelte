<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp25zuqjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp25zuqjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-direction-right-line" {...props}></Icon>
