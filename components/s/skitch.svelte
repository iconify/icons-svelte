<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmnby9hay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wmnby9hay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:skitch" {...props}></Icon>
