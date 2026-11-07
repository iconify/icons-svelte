<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgk4i-bav.css';
import '../../css/z/z3p-nc5qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgk4i-bav"/><path clip-rule="evenodd" class="z3p-nc5qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sun-2-bold" {...props}></Icon>
