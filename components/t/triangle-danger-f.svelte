<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu_vkkbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-3};
const content = `<path class="cu_vkkbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:triangle-danger-f" {...props}></Icon>
