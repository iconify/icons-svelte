<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg9h-rbgi.css';
import '../../css/h/hnwh_8bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="jg9h-rbgi"/><circle class="hnwh_8bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="geo:turf-along" {...props}></Icon>
