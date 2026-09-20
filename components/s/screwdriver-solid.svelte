<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9m6ewbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="p9m6ewbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:screwdriver-solid" {...props}></Icon>
