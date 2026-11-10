<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tinycmxbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tinycmxbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:stroke-line-cap-square" {...props}></Icon>
