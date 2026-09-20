<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syx1i9lex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="syx1i9lex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:web-filled" {...props}></Icon>
