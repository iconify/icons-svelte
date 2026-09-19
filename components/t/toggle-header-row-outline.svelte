<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e83pwdqmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e83pwdqmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:toggle-header-row-outline" {...props}></Icon>
