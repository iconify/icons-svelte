<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1pjk9bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e1pjk9bxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:syringe-solid" {...props}></Icon>
