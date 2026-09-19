<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbr9q9ucb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qbr9q9ucb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:sparkles-sharp" {...props}></Icon>
