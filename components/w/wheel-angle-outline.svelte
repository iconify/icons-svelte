<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2uc92ese.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2uc92ese"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wheel-angle-outline" {...props}></Icon>
