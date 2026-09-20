<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/appne6kbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="appne6kbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:screen-curve" {...props}></Icon>
