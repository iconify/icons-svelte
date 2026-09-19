<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx-tse73g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":727};
const content = `<path class="hx-tse73g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:skype" {...props}></Icon>
