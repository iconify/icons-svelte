<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwdn5hbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mwdn5hbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:vermont" {...props}></Icon>
