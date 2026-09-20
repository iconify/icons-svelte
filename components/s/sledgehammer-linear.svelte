<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x19_ekbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x19_ekbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sledgehammer-linear" {...props}></Icon>
