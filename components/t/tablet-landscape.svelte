<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8ctqoumq.css';
import '../../css/e/e5-idrbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p8ctqoumq"/><path class="e5-idrbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tablet-landscape" {...props}></Icon>
