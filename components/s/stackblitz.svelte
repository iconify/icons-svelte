<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn_e1cb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn_e1cb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:stackblitz" {...props}></Icon>
