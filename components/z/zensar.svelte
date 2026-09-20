<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg4urmbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg4urmbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zensar" {...props}></Icon>
