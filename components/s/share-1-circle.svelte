<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f25raz9at.css';
import '../../css/h/h67twkbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path clip-rule="evenodd" class="f25raz9at"/><path class="h67twkbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:share-1-circle" {...props}></Icon>
