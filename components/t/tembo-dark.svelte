<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd5_iibfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":153,"height":152};
const content = `<path clip-rule="evenodd" class="fd5_iibfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tembo-dark" {...props}></Icon>
