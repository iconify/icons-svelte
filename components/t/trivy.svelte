<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tos43mmlx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tos43mmlx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:trivy" {...props}></Icon>
