<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xya1qabtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xya1qabtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:volume-up-fill" {...props}></Icon>
