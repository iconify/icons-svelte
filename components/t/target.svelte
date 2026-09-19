<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_5nglblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="c_5nglblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:target" {...props}></Icon>
