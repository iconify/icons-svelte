<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/seimh3bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="seimh3bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:square-plus-filled" {...props}></Icon>
