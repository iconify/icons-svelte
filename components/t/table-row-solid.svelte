<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9435tbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t9435tbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:table-row-solid" {...props}></Icon>
