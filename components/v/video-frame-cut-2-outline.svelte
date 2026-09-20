<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py1534b9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="py1534b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:video-frame-cut-2-outline" {...props}></Icon>
