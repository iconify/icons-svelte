<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8n4n_jvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8n4n_jvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:toaster-clock" {...props}></Icon>
