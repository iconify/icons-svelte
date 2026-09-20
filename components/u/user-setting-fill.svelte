<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waq0mlnar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="waq0mlnar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-setting-fill" {...props}></Icon>
