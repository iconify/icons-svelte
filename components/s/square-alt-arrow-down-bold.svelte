<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9fqr6ixu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i9fqr6ixu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-alt-arrow-down-bold" {...props}></Icon>
