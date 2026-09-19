<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuycr8uha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<path class="vuycr8uha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:suitcase" {...props}></Icon>
