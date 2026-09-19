<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni4a_fbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ni4a_fbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:ticket-solid" {...props}></Icon>
