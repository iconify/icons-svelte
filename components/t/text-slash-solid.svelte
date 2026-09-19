<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bubclra3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bubclra3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:text-slash-solid" {...props}></Icon>
