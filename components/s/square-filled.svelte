<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhhkxyita.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bhhkxyita"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:square-filled" {...props}></Icon>
