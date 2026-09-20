<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm-p47dmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dm-p47dmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:setting-o" {...props}></Icon>
