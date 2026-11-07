<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t25cvmbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t25cvmbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:suspension-cross-outline" {...props}></Icon>
