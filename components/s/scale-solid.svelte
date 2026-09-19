<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co2b8uqdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="co2b8uqdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:scale-solid" {...props}></Icon>
