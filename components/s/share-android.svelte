<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbfpxzbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbfpxzbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:share-android" {...props}></Icon>
