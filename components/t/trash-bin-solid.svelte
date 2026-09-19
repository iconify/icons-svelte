<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7p7qz3cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z7p7qz3cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:trash-bin-solid" {...props}></Icon>
