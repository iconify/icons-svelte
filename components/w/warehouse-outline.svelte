<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-xnt587t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v-xnt587t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:warehouse-outline" {...props}></Icon>
