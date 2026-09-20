<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l19hjacna.css';
import '../../css/p/pfrgpji_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l19hjacna"/><path class="pfrgpji_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wapy-dev-dark" {...props}></Icon>
