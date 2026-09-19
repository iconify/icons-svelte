<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv452rm2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":669,"height":681};
const content = `<path class="xv452rm2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:slideshare" {...props}></Icon>
