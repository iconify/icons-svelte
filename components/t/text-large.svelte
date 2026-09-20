<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz00_cbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hz00_cbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:text-large" {...props}></Icon>
