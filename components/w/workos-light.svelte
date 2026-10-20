<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smc74qbot.css';
import '../../css/u/u65_2lbpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":55.4,"height":48};
const content = `<path class="smc74qbot"/><path class="u65_2lbpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:workos-light" {...props}></Icon>
