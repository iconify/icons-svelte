<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojx1uh95k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ojx1uh95k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:salesforce" {...props}></Icon>
