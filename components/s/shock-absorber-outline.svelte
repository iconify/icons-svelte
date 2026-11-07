<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mks2d9e3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mks2d9e3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shock-absorber-outline" {...props}></Icon>
