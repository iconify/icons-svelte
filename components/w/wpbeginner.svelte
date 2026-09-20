<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdd9zacpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jdd9zacpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:wpbeginner" {...props}></Icon>
