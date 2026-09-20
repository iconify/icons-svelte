<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg3mb-7km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kg3mb-7km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:verified-check-bold" {...props}></Icon>
