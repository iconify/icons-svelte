<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zugv0mu1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zugv0mu1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:skip-prev-filled" {...props}></Icon>
