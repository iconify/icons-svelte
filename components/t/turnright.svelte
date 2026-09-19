<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw2h12bnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gw2h12bnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:turnright" {...props}></Icon>
