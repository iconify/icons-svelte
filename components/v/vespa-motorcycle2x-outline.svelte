<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2r2-mbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d2r2-mbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:vespa-motorcycle2x-outline" {...props}></Icon>
