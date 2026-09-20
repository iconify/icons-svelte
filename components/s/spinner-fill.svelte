<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv6qmsbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv6qmsbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:spinner-fill" {...props}></Icon>
