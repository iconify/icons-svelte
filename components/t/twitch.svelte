<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufj9n4bfr.css';
import '../../css/p/pv04-_f7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufj9n4bfr"/><path class="pv04-_f7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:twitch" {...props}></Icon>
