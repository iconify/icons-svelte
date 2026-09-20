<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui3x2lbwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ui3x2lbwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:stop" {...props}></Icon>
