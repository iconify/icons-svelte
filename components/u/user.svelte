<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7daywb0g.css';
import '../../css/m/m8bpqrxix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="a7daywb0g"/><path class="m8bpqrxix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:user" {...props}></Icon>
