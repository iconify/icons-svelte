<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5e579eoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5e579eoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:support-filled" {...props}></Icon>
