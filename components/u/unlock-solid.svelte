<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv3y6zk0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hv3y6zk0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:unlock-solid" {...props}></Icon>
