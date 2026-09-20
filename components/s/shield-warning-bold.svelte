<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k44leqden.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k44leqden"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-warning-bold" {...props}></Icon>
