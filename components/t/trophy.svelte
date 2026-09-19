<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0u2bog3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0u2bog3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:trophy" {...props}></Icon>
