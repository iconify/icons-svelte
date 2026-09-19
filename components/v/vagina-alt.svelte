<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uord8ebkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="uord8ebkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:vagina-alt" {...props}></Icon>
