<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f53is0bjt.css';
import '../../css/a/an4vz7evy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f53is0bjt"/><path class="an4vz7evy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:video-player-laptop-bold" {...props}></Icon>
