<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3mya35-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l3mya35-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:skip-forward-filled" {...props}></Icon>
