<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cie8_kbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cie8_kbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:things" {...props}></Icon>
