<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el_-39bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="el_-39bmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:teeth" {...props}></Icon>
