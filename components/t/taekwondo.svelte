<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj8audbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="pj8audbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:taekwondo" {...props}></Icon>
