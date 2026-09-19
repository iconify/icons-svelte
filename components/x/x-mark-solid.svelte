<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzv4o8oal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tzv4o8oal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:x-mark-solid" {...props}></Icon>
