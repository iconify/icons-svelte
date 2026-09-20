<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiq_k3ghp.css';
import '../../css/p/psisj8b5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fiq_k3ghp"/><path class="psisj8b5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:vinyl-record-player-bold" {...props}></Icon>
