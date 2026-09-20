<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iimb0g9ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iimb0g9ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sitting-tank-toilet-and-droplet" {...props}></Icon>
