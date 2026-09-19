<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjacyrbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":998,"height":1000};
const content = `<path class="qjacyrbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:tudou" {...props}></Icon>
