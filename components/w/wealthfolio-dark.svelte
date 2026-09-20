<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyb-cgbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fyb-cgbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wealthfolio-dark" {...props}></Icon>
