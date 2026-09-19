<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9pw-hbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u9pw-hbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:two-two" {...props}></Icon>
