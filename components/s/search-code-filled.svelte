<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twu1jgkwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twu1jgkwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:search-code-filled" {...props}></Icon>
