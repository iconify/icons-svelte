<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oot7aachb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oot7aachb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:store" {...props}></Icon>
