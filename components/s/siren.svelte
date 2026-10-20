<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwsdt-b2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwsdt-b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:siren" {...props}></Icon>
