<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-sjzebyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-sjzebyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:spatula-fill" {...props}></Icon>
