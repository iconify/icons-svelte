<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxkvu5bej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kxkvu5bej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:signal-solid" {...props}></Icon>
