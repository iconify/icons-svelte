<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us2h0wbnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us2h0wbnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:system-image-outlined" {...props}></Icon>
