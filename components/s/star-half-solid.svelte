<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo98k8b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo98k8b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:star-half-solid" {...props}></Icon>
