<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-4xc8ofo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="f-4xc8ofo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:shield-lefthalf-fill" {...props}></Icon>
