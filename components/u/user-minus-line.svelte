<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_1ow1tug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_1ow1tug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-minus-line" {...props}></Icon>
