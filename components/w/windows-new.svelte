<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfh-c-blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfh-c-blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:windows-new" {...props}></Icon>
