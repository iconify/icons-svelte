<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiw05rb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aiw05rb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tiktok" {...props}></Icon>
