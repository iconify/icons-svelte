<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2nz1si5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h2nz1si5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:video-outline-24px" {...props}></Icon>
