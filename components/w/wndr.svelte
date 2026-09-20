<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0rhc6bwk.css';
import '../../css/v/v73yovbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0rhc6bwk"/><path class="v73yovbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:wndr" {...props}></Icon>
