<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hda2nzbnb.css';
import '../../css/z/zodp_k1_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hda2nzbnb"/><path class="zodp_k1_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spirit-level-48-bold" {...props}></Icon>
