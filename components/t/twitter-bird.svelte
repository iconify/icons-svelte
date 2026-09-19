<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhi9wsb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1003,"height":1000};
const content = `<path class="mhi9wsb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:twitter-bird" {...props}></Icon>
