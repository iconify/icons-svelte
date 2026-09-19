<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymn00fgdm.css';
import '../../css/v/vowsucibp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="ymn00fgdm"/><path class="vowsucibp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:user-add" {...props}></Icon>
