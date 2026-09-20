<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcxm9nb7g.css';
import '../../css/o/o-c62h2ob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcxm9nb7g"/><path class="o-c62h2ob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:system-location-filled" {...props}></Icon>
