<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymayf7r7m.css';
import '../../css/o/ow15xdb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymayf7r7m"/><path class="ow15xdb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-clock-duotone" {...props}></Icon>
