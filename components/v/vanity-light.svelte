<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn26v467x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sn26v467x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vanity-light" {...props}></Icon>
