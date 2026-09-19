<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dldsi0b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dldsi0b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:unreal-engine" {...props}></Icon>
