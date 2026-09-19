<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgzu6kaxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xgzu6kaxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:to-bottom" {...props}></Icon>
