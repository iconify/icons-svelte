<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/meh6rwzlz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="meh6rwzlz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:watch-outline" {...props}></Icon>
