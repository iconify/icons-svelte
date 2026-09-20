<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay3ubnumw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ay3ubnumw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:seat-legroom-normal" {...props}></Icon>
