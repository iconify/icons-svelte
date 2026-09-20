<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezrac2bcq.css';
import '../../css/c/cuj_81b3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezrac2bcq"/><path class="cuj_81b3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:whales" {...props}></Icon>
