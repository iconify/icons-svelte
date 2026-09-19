<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgk67bbts.css';
import '../../css/i/ixe8k5-3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgk67bbts"/><path class="ixe8k5-3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:shuffle-solid" {...props}></Icon>
