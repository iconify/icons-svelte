<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alyfp03um.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="alyfp03um"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:won" {...props}></Icon>
