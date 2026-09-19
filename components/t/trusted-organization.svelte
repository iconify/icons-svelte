<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2yx2bcgg.css';
import '../../css/u/urz-4cihd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2yx2bcgg"/><circle class="urz-4cihd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:trusted-organization" {...props}></Icon>
