<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu3j08bot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xu3j08bot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spinnerr-dark" {...props}></Icon>
