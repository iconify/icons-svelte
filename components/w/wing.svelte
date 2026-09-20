<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kukv2j79e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kukv2j79e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:wing" {...props}></Icon>
