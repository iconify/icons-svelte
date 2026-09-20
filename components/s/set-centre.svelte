<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk3vlyqac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bk3vlyqac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:set-centre" {...props}></Icon>
