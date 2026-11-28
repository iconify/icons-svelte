<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkipm3bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="gkipm3bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:stack-simple-plus-thin" {...props}></Icon>
