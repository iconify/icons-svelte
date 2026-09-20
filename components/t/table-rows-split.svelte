<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb-7hwcld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mb-7hwcld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:table-rows-split" {...props}></Icon>
