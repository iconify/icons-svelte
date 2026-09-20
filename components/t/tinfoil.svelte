<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk7wtbc2i.css';
import '../../css/t/tqqkmcc0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wk7wtbc2i"/><path class="tqqkmcc0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tinfoil" {...props}></Icon>
