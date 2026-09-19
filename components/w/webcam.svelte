<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9ynb3b_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i9ynb3b_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:webcam" {...props}></Icon>
