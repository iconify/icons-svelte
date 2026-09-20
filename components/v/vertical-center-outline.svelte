<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-s55l-ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q-s55l-ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:vertical-center-outline" {...props}></Icon>
