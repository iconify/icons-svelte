<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wabg6tf_x.css';
import '../../css/c/ck9b5hbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wabg6tf_x"/><path class="ck9b5hbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:services" {...props}></Icon>
