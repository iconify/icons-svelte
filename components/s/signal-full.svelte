<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9ob-jvxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9ob-jvxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:signal-full" {...props}></Icon>
