<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boq9-pb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="boq9-pb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:weight" {...props}></Icon>
