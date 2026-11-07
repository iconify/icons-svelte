<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-e9pdl7a.css';
import '../../css/v/vnqotyhmz.css';
import '../../css/j/jb__gobaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-e9pdl7a"/><path class="vnqotyhmz"/><path class="jb__gobaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:streets-bold" {...props}></Icon>
