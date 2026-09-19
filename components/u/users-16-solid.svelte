<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su_apmhpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="su_apmhpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:users-16-solid" {...props}></Icon>
