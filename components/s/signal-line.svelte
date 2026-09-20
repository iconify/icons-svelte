<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue6w-gb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue6w-gb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:signal-line" {...props}></Icon>
