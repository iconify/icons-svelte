<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do3yepbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="do3yepbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:voice-cricle" {...props}></Icon>
