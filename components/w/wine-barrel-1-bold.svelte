<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9nbipb_i.css';
import '../../css/v/vw1ziqbrv.css';
import '../../css/i/izh8f-hbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9nbipb_i"/><path class="vw1ziqbrv"/><path class="izh8f-hbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:wine-barrel-1-bold" {...props}></Icon>
