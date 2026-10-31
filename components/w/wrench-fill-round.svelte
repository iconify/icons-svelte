<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbami-btp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbami-btp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wrench-fill-round" {...props}></Icon>
