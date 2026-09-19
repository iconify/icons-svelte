<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4sdkkska.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="f4sdkkska"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:views-fill-26" {...props}></Icon>
