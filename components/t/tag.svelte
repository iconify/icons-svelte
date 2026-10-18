<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9r3v0beh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9r3v0beh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:tag" {...props}></Icon>
