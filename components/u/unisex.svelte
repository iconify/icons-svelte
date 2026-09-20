<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfomdp99f.css';
import '../../css/c/clgt-tmqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<circle class="xfomdp99f"/><path class="clgt-tmqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:unisex" {...props}></Icon>
