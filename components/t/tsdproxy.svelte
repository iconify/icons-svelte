<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl35fttde.css';
import '../../css/v/vv1q87bgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="yl35fttde"/><path class="vv1q87bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tsdproxy" {...props}></Icon>
