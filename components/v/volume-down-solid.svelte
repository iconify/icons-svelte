<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtmjq4l9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtmjq4l9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:volume-down-solid" {...props}></Icon>
