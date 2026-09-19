<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwlz_0bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lwlz_0bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:settings-compact" {...props}></Icon>
