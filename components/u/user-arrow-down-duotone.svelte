<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1rh2qbtt.css';
import '../../css/o/ow15xdb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1rh2qbtt"/><path class="ow15xdb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-arrow-down-duotone" {...props}></Icon>
