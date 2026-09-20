<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boq6ejbul.css';
import '../../css/z/zlg69lb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="boq6ejbul"/><path class="zlg69lb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zrok" {...props}></Icon>
