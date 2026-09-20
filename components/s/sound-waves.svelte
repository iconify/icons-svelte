<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8e2a022h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8e2a022h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:sound-waves" {...props}></Icon>
