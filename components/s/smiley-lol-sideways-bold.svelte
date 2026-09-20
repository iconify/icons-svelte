<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejos-9bsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejos-9bsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:smiley-lol-sideways-bold" {...props}></Icon>
