<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iajba_bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iajba_bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:standard-definition" {...props}></Icon>
