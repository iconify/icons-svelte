<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eprk_cmdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eprk_cmdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tshirt-plus" {...props}></Icon>
