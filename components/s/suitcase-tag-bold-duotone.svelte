<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dciv8jbgc.css';
import '../../css/z/zo2kgwbhm.css';
import '../../css/h/hd5dgobzc.css';
import '../../css/k/kyfybbbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dciv8jbgc"/><path class="zo2kgwbhm"/><path class="hd5dgobzc"/><path clip-rule="evenodd" class="kyfybbbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:suitcase-tag-bold-duotone" {...props}></Icon>
