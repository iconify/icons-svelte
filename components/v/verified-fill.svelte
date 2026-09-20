<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk4-p0bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vk4-p0bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:verified-fill" {...props}></Icon>
