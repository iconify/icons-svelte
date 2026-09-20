<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl7hxid5w.css';
import '../../css/r/rs4bqbchn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl7hxid5w"/><path class="rs4bqbchn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:urus" {...props}></Icon>
