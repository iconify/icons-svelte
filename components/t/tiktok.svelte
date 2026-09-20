<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suqoae0-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="suqoae0-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:tiktok" {...props}></Icon>
