<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks-6myb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks-6myb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:trending-up-duotone" {...props}></Icon>
