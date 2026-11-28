<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-3sfv_0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary t-3sfv_0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tooth-duotone" {...props}></Icon>
