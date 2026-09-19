<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9grvyq5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="f9grvyq5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:spinner-3" {...props}></Icon>
