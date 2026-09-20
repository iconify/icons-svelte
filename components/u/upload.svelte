<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1zwuffkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1zwuffkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:upload" {...props}></Icon>
