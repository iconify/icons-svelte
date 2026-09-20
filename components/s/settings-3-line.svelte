<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slxfccb9c.css';
import '../../css/n/nmf1tu78z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slxfccb9c"/><path class="nmf1tu78z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-3-line" {...props}></Icon>
