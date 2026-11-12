<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trl7bqbmp.css';
import '../../css/d/d9m02bchl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="trl7bqbmp"/><path class="d9m02bchl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spirit-airlines" {...props}></Icon>
