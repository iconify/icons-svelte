<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crdgngbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crdgngbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:vidicon-fill" {...props}></Icon>
