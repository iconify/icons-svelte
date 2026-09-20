<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apws8rb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="apws8rb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:share-2" {...props}></Icon>
