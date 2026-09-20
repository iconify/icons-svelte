<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxfmooi8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qxfmooi8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:toilet-sign-man-flat" {...props}></Icon>
