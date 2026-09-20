<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_lpyv8on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_lpyv8on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sanity" {...props}></Icon>
