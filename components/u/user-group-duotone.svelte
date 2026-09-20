<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9wncd_8q.css';
import '../../css/m/mlk-ksb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9wncd_8q"/><path class="mlk-ksb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-group-duotone" {...props}></Icon>
