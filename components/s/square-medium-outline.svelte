<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al9z_qb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="al9z_qb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:square-medium-outline" {...props}></Icon>
