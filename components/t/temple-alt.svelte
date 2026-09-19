<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5dfnsyvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="m5dfnsyvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:temple-alt" {...props}></Icon>
