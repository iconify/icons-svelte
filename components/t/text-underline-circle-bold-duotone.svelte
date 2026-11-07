<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtmuzrg2o.css';
import '../../css/u/u9tzwj7ok.css';
import '../../css/b/bzy5eobti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtmuzrg2o"/><path class="u9tzwj7ok"/><path class="bzy5eobti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-underline-circle-bold-duotone" {...props}></Icon>
