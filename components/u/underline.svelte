<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk85vbjug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hk85vbjug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:underline" {...props}></Icon>
