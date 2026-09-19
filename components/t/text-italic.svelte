<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/god5aqbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="god5aqbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:text-italic" {...props}></Icon>
