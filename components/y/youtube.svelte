<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqmd64fvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="pqmd64fvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:youtube" {...props}></Icon>
