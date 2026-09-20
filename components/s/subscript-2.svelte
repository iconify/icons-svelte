<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkslvhbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkslvhbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:subscript-2" {...props}></Icon>
