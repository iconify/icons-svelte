<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fup7tzn3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fup7tzn3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:user-talk-1-filled" {...props}></Icon>
