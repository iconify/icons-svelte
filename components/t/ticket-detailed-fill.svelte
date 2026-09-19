<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffj7q5byu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ffj7q5byu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:ticket-detailed-fill" {...props}></Icon>
