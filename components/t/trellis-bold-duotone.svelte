<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4-mns66q.css';
import '../../css/c/c52keb9qe.css';
import '../../css/x/x8znsxq4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4-mns66q"/><path class="c52keb9qe"/><path clip-rule="evenodd" class="x8znsxq4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:trellis-bold-duotone" {...props}></Icon>
