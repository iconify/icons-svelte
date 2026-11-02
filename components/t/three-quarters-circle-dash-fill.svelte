<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm_uf7cdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm_uf7cdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:three-quarters-circle-dash-fill" {...props}></Icon>
