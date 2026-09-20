<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrwj86bxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrwj86bxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:scan-face" {...props}></Icon>
