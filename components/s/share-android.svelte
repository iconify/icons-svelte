<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex4nlwbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ex4nlwbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:share-android" {...props}></Icon>
