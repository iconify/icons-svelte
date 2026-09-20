<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhd6nmq1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jhd6nmq1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-up-bold" {...props}></Icon>
