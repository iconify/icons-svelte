<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br3d1gslt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":467,"height":512};
const content = `<path class="br3d1gslt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:typedoc" {...props}></Icon>
