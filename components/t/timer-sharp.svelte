<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygy8b74rs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ygy8b74rs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:timer-sharp" {...props}></Icon>
