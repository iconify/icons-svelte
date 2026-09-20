<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4lzkobkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n4lzkobkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:square-20-solid" {...props}></Icon>
