<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l10h6cbda.css';
import '../../css/y/yv3sgvbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l10h6cbda"/><path clip-rule="evenodd" class="yv3sgvbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stretching-bold" {...props}></Icon>
