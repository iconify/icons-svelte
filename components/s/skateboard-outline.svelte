<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km5m1bcov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="km5m1bcov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:skateboard-outline" {...props}></Icon>
