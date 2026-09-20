<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk_debboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk_debboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:send" {...props}></Icon>
