<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppyevyb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ppyevyb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:waves-right" {...props}></Icon>
