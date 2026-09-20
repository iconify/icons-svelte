<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4r3qou8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4r3qou8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:truck-arrow-up-sharp" {...props}></Icon>
