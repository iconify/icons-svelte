<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1587w2qu.css';
import '../../css/o/ow15xdb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1587w2qu"/><path class="ow15xdb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-envelope-duotone" {...props}></Icon>
