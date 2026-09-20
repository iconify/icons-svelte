<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu3wncbjp.css';
import '../../css/q/qa69btbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu3wncbjp"/><path class="qa69btbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:users-crown-light" {...props}></Icon>
