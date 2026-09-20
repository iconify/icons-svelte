<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li9yf9n-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="li9yf9n-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:seal-shape-bold" {...props}></Icon>
