<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id4gopsxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="id4gopsxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-arrow-right-up-bold" {...props}></Icon>
