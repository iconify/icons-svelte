<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s71_e0bzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":624,"height":737};
const content = `<path class="s71_e0bzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:save" {...props}></Icon>
