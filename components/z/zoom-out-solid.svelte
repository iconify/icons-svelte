<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv2zj9ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iv2zj9ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:zoom-out-solid" {...props}></Icon>
