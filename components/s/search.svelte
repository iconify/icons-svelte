<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow0wjkqcp.css';
import '../../css/a/alyn96y6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ow0wjkqcp"/><path class="alyn96y6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:search" {...props}></Icon>
