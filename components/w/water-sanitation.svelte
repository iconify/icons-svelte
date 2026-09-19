<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pepi70ffa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pepi70ffa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:water-sanitation" {...props}></Icon>
