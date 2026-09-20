<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrb495m5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrb495m5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:wemo" {...props}></Icon>
