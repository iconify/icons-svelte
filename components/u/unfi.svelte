<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejk70mm4e.css';
import '../../css/a/agnov_a2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejk70mm4e"/><path class="agnov_a2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:unfi" {...props}></Icon>
