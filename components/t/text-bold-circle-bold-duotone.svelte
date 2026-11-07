<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtmuzrg2o.css';
import '../../css/v/v35_57ben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtmuzrg2o"/><path clip-rule="evenodd" class="v35_57ben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-bold-circle-bold-duotone" {...props}></Icon>
