<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw4qccbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw4qccbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:upload" {...props}></Icon>
