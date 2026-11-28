<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg-3wwblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kg-3wwblx primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:signal-low-duotone" {...props}></Icon>
