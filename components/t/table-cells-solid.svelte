<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8t4lj5ym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i8t4lj5ym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:table-cells-solid" {...props}></Icon>
