<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkafj-b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wkafj-b4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:surface-front-outline" {...props}></Icon>
