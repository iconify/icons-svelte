<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmxc4xb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cmxc4xb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:syringe-outline-24px" {...props}></Icon>
