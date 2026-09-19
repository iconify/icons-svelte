<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqzpwybhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="jqzpwybhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:u-turn-sign-bold" {...props}></Icon>
